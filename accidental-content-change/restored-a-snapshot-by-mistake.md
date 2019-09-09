# Restored a snapshot by mistake

Restoring a snapshot will overwrite the contents of your current state with the contents of the snapshot being restored. When a snapshot is restored, DataHub automatically creates a backup snapshot of the current state before overwriting its content. Therefore, to revert a snapshot restoration operation, you can simply restore the backup snapshot that was automatically created after the first restoration operation.

For example, say you have a snapshot called Snapshot\_1 in your instance. By mistake, you restore Snapshot\_1, and two things happen: first, DataHub creates a backup snapshot of your current state with its existing content \(let's call it Snapshot1\_backup\), and second, the contents of the current state get overwritten by the contents of Snapshot\_1. If you have accidentally Snapshot\_1, and you want to revert this operation, you can restore Snapshot1\_backup which will again overwrite the contents of the current state with what it had before the first snapshot restoration was performed.

